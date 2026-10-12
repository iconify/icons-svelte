<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yq1rrzxbk.css';
import '../../css/y/yx-p2ubml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yq1rrzxbk"/><path class="yx-p2ubml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:text-color-fill-20" {...props}></Icon>
