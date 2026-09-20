<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wzt857t0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wzt857t0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:usaa-light" {...props}></Icon>
