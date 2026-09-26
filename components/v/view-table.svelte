<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iagkg8bla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="iagkg8bla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:view-table" {...props}></Icon>
