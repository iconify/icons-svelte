<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yy-f4-1dv.css';
import '../../css/l/l3-5_c46r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yy-f4-1dv"/><path clip-rule="evenodd" class="l3-5_c46r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:si" {...props}></Icon>
