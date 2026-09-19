<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ur1u_fp9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ur1u_fp9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:sliding-barndoor-open" {...props}></Icon>
