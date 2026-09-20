<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2y3hnb5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f2y3hnb5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:snapchat-light" {...props}></Icon>
