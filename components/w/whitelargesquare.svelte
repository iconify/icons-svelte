<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gln9e_ezj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gln9e_ezj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:whitelargesquare" {...props}></Icon>
