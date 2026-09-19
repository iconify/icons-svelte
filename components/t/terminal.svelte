<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/efdikdyoo.css';
import '../../css/e/ehoajibnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="efdikdyoo"/><path clip-rule="evenodd" class="ehoajibnd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:terminal" {...props}></Icon>
