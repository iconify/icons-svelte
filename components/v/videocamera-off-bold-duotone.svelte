<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yd4l-wycb.css';
import '../../css/p/prycr4uyu.css';
import '../../css/g/gn_f1tn5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yd4l-wycb"/><path class="prycr4uyu"/><path class="gn_f1tn5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:videocamera-off-bold-duotone" {...props}></Icon>
