<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwofekvjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dwofekvjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rustpad-dark" {...props}></Icon>
