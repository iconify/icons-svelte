<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uieshjzys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="uieshjzys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:thumb-down" {...props}></Icon>
