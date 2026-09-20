<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2cs6yhfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g2cs6yhfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:zaneops" {...props}></Icon>
