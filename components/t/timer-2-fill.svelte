<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vu2s_jbwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vu2s_jbwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:timer-2-fill" {...props}></Icon>
