<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5g7mrbhx.css';
import '../../css/h/hnc9r9bik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g5g7mrbhx"/><path class="hnc9r9bik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:typestash-light" {...props}></Icon>
