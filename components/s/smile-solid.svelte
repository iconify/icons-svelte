<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-v5zjbwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z-v5zjbwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:smile-solid" {...props}></Icon>
