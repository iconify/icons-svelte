<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_ruscb-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v_ruscb-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:send-check" {...props}></Icon>
