<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/bsom-6btp.css';
import '../../css/h/hg4v63b4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="bsom-6btp"/><path class="hg4v63b4m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:square-2-stack-16-solid" {...props}></Icon>
