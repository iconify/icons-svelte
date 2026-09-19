<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ef4-qabdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ef4-qabdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:table-of-contents" {...props}></Icon>
