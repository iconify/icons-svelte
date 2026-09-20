<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4s-3hy_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p4s-3hy_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:wireless-charge" {...props}></Icon>
