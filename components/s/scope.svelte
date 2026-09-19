<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/dqf-rdblp.css';
import '../../css/v/vpzju-cqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="cuyn6tgcc"><path class="dqf-rdblp"/><path class="vpzju-cqu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:scope" {...props}></Icon>
