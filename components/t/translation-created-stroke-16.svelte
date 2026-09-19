<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/de93w3jem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="de93w3jem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:translation-created-stroke-16" {...props}></Icon>
