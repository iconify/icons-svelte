<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t99fn8lrk.css';
import '../../css/c/cna8fmbzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="t99fn8lrk"/><path class="cna8fmbzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:teabag" {...props}></Icon>
