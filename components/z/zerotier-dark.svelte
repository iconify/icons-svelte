<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhr29gb-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uhr29gb-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:zerotier-dark" {...props}></Icon>
