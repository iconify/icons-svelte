<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sk0h4l9rx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sk0h4l9rx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wireguard-transparent-dark" {...props}></Icon>
