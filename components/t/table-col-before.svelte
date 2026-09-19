<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wai40rbwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wai40rbwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:table-col-before" {...props}></Icon>
