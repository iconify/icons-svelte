<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f770scbge.css';
import '../../css/b/bgy0nnrsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f770scbge"/><path class="bgy0nnrsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:social-rewards-like-bubble" {...props}></Icon>
