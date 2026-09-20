<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbppjpbmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mbppjpbmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:rubbish-bin" {...props}></Icon>
