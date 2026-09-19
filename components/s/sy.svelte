<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/u/umbnhhb9z.css';
import '../../css/m/mdsn5dp1e.css';
import '../../css/j/j2i80_c1v.css';
import '../../css/b/bakiw7wnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="umbnhhb9z"/><path class="mdsn5dp1e"/><path class="j2i80_c1v"/><path class="bakiw7wnb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flagpack:sy" {...props}></Icon>
