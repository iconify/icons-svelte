<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wj8efxbhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wj8efxbhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:view-grid-add" {...props}></Icon>
