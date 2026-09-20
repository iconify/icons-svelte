<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lt8x5gmuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lt8x5gmuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:sandstorm-light" {...props}></Icon>
