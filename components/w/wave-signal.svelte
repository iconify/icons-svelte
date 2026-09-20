<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfdkbab2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="nfdkbab2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:wave-signal" {...props}></Icon>
