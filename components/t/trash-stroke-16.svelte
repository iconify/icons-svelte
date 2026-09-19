<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezshxbbzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ezshxbbzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:trash-stroke-16" {...props}></Icon>
