<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcm2tjbsz.css';
import '../../css/d/dz7650h2w.css';
import '../../css/u/uol8h3pbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vcm2tjbsz"/><path clip-rule="evenodd" class="dz7650h2w"/><path class="uol8h3pbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:sparks-off" {...props}></Icon>
