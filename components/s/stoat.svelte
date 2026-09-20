<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ycbseobgb.css';
import '../../css/d/dbcsx4b-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="ycbseobgb"/><path class="dbcsx4b-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:stoat" {...props}></Icon>
