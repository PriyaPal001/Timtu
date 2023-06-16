<section class="text-gray-600 body-font mx-20">
  <div
    class="container mx-auto flex border-4 border-red-500 px-24 py- md:flex-row flex-col items-center"
  >
    <div
      class="lg:flex-grow md:w-1/2 lg:pr-24 md:pr-16 flex flex-col md:items-start md:text-left mb-16 md:mb-0 items-center text-center"
    >
      <h1
        class="title-font sm:text-4xl text-3xl mb-4 font-medium text-gray-900"
      >
        Get unique
        <br class="hidden lg:inline-block" />components
      </h1>
      <p class="mb-8 leading-relaxed">
        You can get unique components for your project here.
      </p>
      <div class="flex justify-center">
        <button
          class="inline-flex text-white bg-indigo-500 border-0 py-2 px-6 focus:outline-none hover:bg-indigo-600 rounded text-lg"
          >Get started</button
        >
        <button
          class="ml-4 inline-flex text-gray-700 bg-gray-100 border-0 py-2 px-6 focus:outline-none hover:bg-gray-200 rounded text-lg"
          >learn more</button
        >
      </div>
    </div>
    <div
      class="lg:max-w-lg lg:w-full md:w-1/2 w-5/6 border-4 mx-4 my-10 border-red-500"
    >
      <img
        class="object-cover object-center rounded h-80"
        alt="hero"
        src="https://i.pinimg.com/564x/44/c9/72/44c972faa265ca316ebf415a531950b6.jpg"
      />
    </div>
  </div>
</section>

<div class="parent">
  <div class="div1 border-4 border-red-400 m-8 flex flex-row">
    <!-- <h1>Hello</h1>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Vitae maiores at voluptates, aspernatur perferendis consectetur dolorum consequatur minima exercitationem iste.</p>
    <img
      class="object-cover object-center rounded img1 my-10"
      alt="hero"
      src="https://img.freepik.com/free-vector/design-structure-matrix-abstract-concept-vector-illustration-project-visual-representation-system-analysis-project-management-organization-team-product-component-timeframe-abstract-metaphor_335657-2943.jpg?size=626&ext=jpg&uid=R87870808&ga=GA1.2.1007551031.1668626592&semt=sph"
    /> -->
      <div
    class="container mx-auto flex p-5 md:flex-row flex-col items-center"
    >
    <div
    class="lg:flex-grow md:w-1/2 lg:pr-24 md:pr-16 flex flex-col md:items-start  mb-16 md:mb-0 items-center text-center"
    >
    <h1
      class="title-font sm:text-4xl text-3xl mb-4 font-medium text-gray-900"
    >
    welcome
    <br class="hidden lg:inline-block" />to timtu
    </h1>
      <p class="mb-8 leading-relaxed">
        You can get unique components for your project here.
      </p>
      <div class="flex justify-center">
        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Aperiam, quas.

        </p>
      </div>
    </div>
    <div
      class="lg:max-w-lg lg:w-full md:w-1/2 w-5/6 "
    >
      <img
        class="object-cover object-center rounded h-80"
        alt="hero"
        src="https://i.pinimg.com/236x/37/84/66/3784661240280fc8a63511889e6094c3.jpg"
      />
    </div>
  </div>
  </div>
  <div class="div2 border-4 border-red-400 m-8">
    <div>
      <img
    class="object-cover object-center rounded h-full"
    alt="hero"
    src="https://img.freepik.com/free-vector/design-structure-matrix-abstract-concept-vector-illustration-project-visual-representation-system-analysis-project-management-organization-team-product-component-timeframe-abstract-metaphor_335657-2943.jpg?size=626&ext=jpg&uid=R87870808&ga=GA1.2.1007551031.1668626592&semt=sph"
    />
    </div>
    <div>
      <h1 class="title-font sm:text-4xl text-3xl mb-4 font-medium text-gray-900">Hello</h1>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Vitae maiores at voluptates, aspernatur perferendis consectetur dolorum consequatur minima exercitationem iste.</p>
    </div>
  </div>
  <div class="div3 border-4 border-red-400 m-8">
    <div>
      <h1 class="title-font sm:text-4xl text-3xl mb-4 font-medium text-gray-900">Hello</h1>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Vitae maiores at voluptates, aspernatur perferendis consectetur dolorum consequatur minima exercitationem iste.</p>
    </div>
    <div>
      <img
      class="object-cover object-center rounded h-full"
      alt="hero"
      src="https://i.pinimg.com/236x/2f/7b/c9/2f7bc92a0be3b495d5072ff725524b49.jpg"
    />
    </div>
  </div>
</div>

<style>
  .parent {
    display: grid;
    grid-template-columns: repeat(8, 1fr);
    grid-template-rows: repeat(5, 1fr);
    grid-column-gap: 0px;
    grid-row-gap: 0px;
  }

  .div1 {
    grid-area: 1 / 1 / 6 / 5;
  }
  .div2 {
    grid-area: 1 / 5 / 6 / 7;
  }
  .div3 {
    grid-area: 1 / 7 / 6 / 9;
  }

  .img1 {
    height: 300px;
    width: 300px;
  }
</style>
