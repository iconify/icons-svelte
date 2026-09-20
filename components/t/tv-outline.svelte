<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/o8kjugm3b.css';
import '../../css/l/la2f6ep6a.css';
import '../../css/n/njkn9wwty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="o8kjugm3b"/><path class="la2f6ep6a"/><path class="njkn9wwty"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:tv-outline" {...props}></Icon>
