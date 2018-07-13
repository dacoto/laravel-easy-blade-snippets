# [Laravel Easy Blade Snippets](https://marketplace.visualstudio.com/items?itemName=dacoto.laravel-easy-blade-snippets)

## Screenshot

![Demo](https://github.com/dacoto/laravel-easy-blade-snippets/raw/master/images/screenshot.gif)

Laravel blade snippets for Visual Studio Code.

> Suggest Laravel related extension: [Laravel 5 Snippets](https://marketplace.visualstudio.com/items?itemName=onecentlin.laravel5-snippets)

## Features

* Laravel blade snippets

## Laravel Blade Snippets

| Trigger                 | Snippet                                                  |
|-------------------------|----------------------------------------------------------|
| blade-extends           | @extends                                                 |
| blade-yield             | @yield                                                   |
| blade-section           | @section...@endsection                                   |
| blade-section-show      | @section...@show                                         |
| blade-if                | @if...@endif                                             |
| blade-if-else           | @if...@else...@endif                                     |
| blade-unless            | @unless...@endunless                                     |
| blade-has-section       | @hasSection...@else...@endif                             |
| blade-for               | @for...@endfor                                           |
| blade-foreach           | @foreach...@endforeach                                   |
| blade-forelse           | @forelse...@empty...@endforelse                          |
| blade-while             | @while...@endwhile                                       |
| blade-each              | @each                                                    |
| blade-push              | @push...@endpush                                         |
| blade-stack             | @stack                                                   |
| blade-inject            | @inject                                                  |
| blade-comment           | {{-- comment --}}                                        |
| blade-echo              | {{ $data }}                                              |
| blade-echo-html         | {!! $html !!}                                            |
| blade-echo-raw          | @{{ variable }}                                          |
| blade-can               | @can...@endcan (v5.1)                                    |
| blade-can-elsecan       | @can...@elsecan...@endcan (v5.1)                         |
| blade-cannot            | @cannot...@endcannot (v5.3)                              |
| blade-cannot-elsecannot | @cannot...@elsecannot...@endcannot                       |
| blade-verbatim          | @verbatim...@endverbatim  (v5.3)                         |
| blade-php               | @php...@endphp  (v5.3)                                   |
| blade-includeIf         | @includeIf  (v5.3)                                       |
| blade-includeWhen       | @includeWhen (v5.4)                                      |
| blade-includeFirst      | @includeFirst (v5.5)                                     |
| blade-component         | @component...@endcomponent (v5.4)                        |
| blade-slot              | @slot...@endslot (v5.4)                                  |
| blade-isset             | @isset...@endisset (v5.4)                                |
| blade-empty             | @empty...@endempty (v5.4)                                |
| blade-auth              | @auth...@endauth (v5.5)                                  |
| blade-guest             | @guest...@endguest (v5.5)                                |
| blade-switch            | @switch...@case...@endswitch                             |
| blade-lang              | @lang                                                    |
| blade-loop              | $loop->(index,remaining,count,first,last,depth,parent)   |
| blade-loop-first        | @if($loop->first)...@endif                               |
| blade-loop-last         | @if($loop->last)...@endif                                |
| blade-csrf              | @csrf                                                    |
| blade-method            | @method(...)                                             |
| blade-dump              | @dump(...)                                               |