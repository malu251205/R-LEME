import React from "react";

export default function Home() {
  return (
    <div className="min-h-screen bg-pink-100 text-gray-900">
      <header className="bg-black text-white p-4 text-center text-xl font-bold">
        R@ Leme - Produtos de Beleza
      </header>
      
      <main className="p-6">
        <section className="bg-white p-4 rounded-xl shadow-md text-center">
          <h1 className="text-2xl font-semibold text-pink-500">Bem-vindo à R@ Leme</h1>
          <p className="text-gray-700 mt-2">Os melhores produtos de beleza para você!</p>
        </section>
      </main>

      <footer className="bg-black text-white text-center p-4 mt-6">
        &copy; 2025 R@ Leme - Todos os direitos reservados.
      </footer>
    </div>
  );
}
