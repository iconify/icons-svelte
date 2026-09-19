<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i82ymobjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":536,"height":512};
const content = `<path class="i82ymobjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:star-half-alt" {...props}></Icon>
