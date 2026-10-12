<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cjqq4fblg.css';
import '../../css/j/jeqtdlb7k.css';
import '../../css/y/yplpaeb1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="cjqq4fblg"/><path class="jeqtdlb7k"/><path class="yplpaeb1m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:search-x-duotone" {...props}></Icon>
