<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tw6xa2_bl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tw6xa2_bl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:text-direction-right-fill" {...props}></Icon>
