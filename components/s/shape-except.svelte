<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2lsh0bhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="r2lsh0bhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:shape-except" {...props}></Icon>
