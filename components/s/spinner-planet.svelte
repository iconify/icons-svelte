<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eelx_9v_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eelx_9v_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:spinner-planet" {...props}></Icon>
