<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isej-pbln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1408};
const content = `<path class="isej-pbln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:unsorted" {...props}></Icon>
