<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cp8lrpbea.css';
import '../../css/i/isx_b_b0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cp8lrpbea"/><path clip-rule="evenodd" class="isx_b_b0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:running-round-bold" {...props}></Icon>
