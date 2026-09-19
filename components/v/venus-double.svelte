<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rp86vqbjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="rp86vqbjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:venus-double" {...props}></Icon>
