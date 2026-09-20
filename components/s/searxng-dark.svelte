<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/shyfh5blv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="shyfh5blv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:searxng-dark" {...props}></Icon>
