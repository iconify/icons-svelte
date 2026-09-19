<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpqzzfw7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="hpqzzfw7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:stripe-s" {...props}></Icon>
