<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gyqdx1fbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gyqdx1fbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:turing-smart-screen-dark" {...props}></Icon>
