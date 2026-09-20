<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xv07z_p7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xv07z_p7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:triangle" {...props}></Icon>
