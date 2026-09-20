<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iznn3mbeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="iznn3mbeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:tshirt" {...props}></Icon>
