<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/as5gy5g_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="as5gy5g_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:solus" {...props}></Icon>
