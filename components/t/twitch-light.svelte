<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9pu_gbnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p9pu_gbnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:twitch-light" {...props}></Icon>
