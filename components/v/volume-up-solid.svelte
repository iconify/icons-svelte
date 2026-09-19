<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/ti3lcux8x.css';
import '../../css/g/gjjyej82e.css';
import '../../css/a/ae894nmnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ti3lcux8x"/><path clip-rule="evenodd" class="gjjyej82e"/><path clip-rule="evenodd" class="ae894nmnu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:volume-up-solid" {...props}></Icon>
