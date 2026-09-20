<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b00az4bsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b00az4bsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:umami-dark" {...props}></Icon>
