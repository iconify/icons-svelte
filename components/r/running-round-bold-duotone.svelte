<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/i7991xb5z.css';
import '../../css/m/muotmj8bl.css';
import '../../css/m/mc2zb0bvp.css';
import '../../css/v/vi2_iacgi.css';
import '../../css/n/n3ijr1bwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="i7991xb5z"/><path clip-rule="evenodd" class="muotmj8bl"/><g class="mc2zb0bvp"><path class="vi2_iacgi"/><path class="n3ijr1bwe"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:running-round-bold-duotone" {...props}></Icon>
