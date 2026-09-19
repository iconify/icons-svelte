<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvoz726yu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qvoz726yu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:square-solid" {...props}></Icon>
