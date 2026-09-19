<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kibv5k5sy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kibv5k5sy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:sensor" {...props}></Icon>
