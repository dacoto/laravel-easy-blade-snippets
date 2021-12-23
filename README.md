# [Laravel Easy Blade Snippets](https://marketplace.visualstudio.com/items?itemName=dacoto.laravel-easy-blade-snippets)

## Screenshot

![Demo](/images/screenshot.gif)

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
| blade-can               | @can...@endcan                                           |
| blade-can-elsecan       | @can...@elsecan...@endcan                                |
| blade-cannot            | @cannot...@endcannot                                     |
| blade-cannot-elsecannot | @cannot...@elsecannot...@endcannot                       |
| blade-verbatim          | @verbatim...@endverbatim                                 |
| blade-php               | @php...@endphp                                           |
| blade-includeIf         | @includeIf                                               |
| blade-includeWhen       | @includeWhen                                             |
| blade-includeFirst      | @includeFirst                                            |
| blade-component         | @component...@endcomponent                               |
| blade-slot              | @slot...@endslot                                         |
| blade-isset             | @isset...@endisset                                       |
| blade-empty             | @empty...@endempty                                       |
| blade-auth              | @auth...@endauth                                         |
| blade-guest             | @guest...@endguest                                       |
| blade-switch            | @switch...@case...@endswitch                             |
| blade-lang              | @lang                                                    |
| blade-loop              | $loop->(index,remaining,count,first,last,depth,parent)   |
| blade-loop-first        | @if($loop->first)...@endif                               |
| blade-loop-last         | @if($loop->last)...@endif                                |
| blade-csrf              | @csrf                                                    |
| blade-method            | @method(...)                                             |
| blade-dump              | @dump(...)                                               |
