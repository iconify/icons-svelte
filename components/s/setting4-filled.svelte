<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/rdkk-6buh.css';
import '../../css/b/b9c76joug.css';
import '../../css/y/yz124rbdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rdkk-6buh"/><path class="b9c76joug"/><path class="yz124rbdu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:setting4-filled" {...props}></Icon>
