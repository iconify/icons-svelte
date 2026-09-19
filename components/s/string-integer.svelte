<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4b-u4sic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o4b-u4sic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:string-integer" {...props}></Icon>
