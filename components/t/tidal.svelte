<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6vsawb7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w6vsawb7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tidal" {...props}></Icon>
