<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gna5_sg5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gna5_sg5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:whitelatincross" {...props}></Icon>
