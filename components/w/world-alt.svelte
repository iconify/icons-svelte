<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pj2ntd1ke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="pj2ntd1ke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:world-alt" {...props}></Icon>
