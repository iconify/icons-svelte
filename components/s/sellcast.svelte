<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzxff1zbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="uzxff1zbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:sellcast" {...props}></Icon>
