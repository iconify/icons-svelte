<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5-9h0xfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o5-9h0xfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:windy" {...props}></Icon>
