<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unvf2ewqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="unvf2ewqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:service" {...props}></Icon>
