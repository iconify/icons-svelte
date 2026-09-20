<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ce61z2uyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ce61z2uyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:slack-dark" {...props}></Icon>
