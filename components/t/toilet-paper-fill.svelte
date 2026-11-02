<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zkwozubwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zkwozubwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:toilet-paper-fill" {...props}></Icon>
