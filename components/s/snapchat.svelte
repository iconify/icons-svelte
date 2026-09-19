<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h0bsct1rm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="h0bsct1rm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:snapchat" {...props}></Icon>
