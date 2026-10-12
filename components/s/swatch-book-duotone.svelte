<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/jzfnhqbvm.css';
import '../../css/b/b7ow5c9sc.css';
import '../../css/a/a80jsmv5h.css';
import '../../css/u/u39fewb1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="jzfnhqbvm"/><path class="b7ow5c9sc"/><path class="a80jsmv5h"/><path class="u39fewb1w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:swatch-book-duotone" {...props}></Icon>
