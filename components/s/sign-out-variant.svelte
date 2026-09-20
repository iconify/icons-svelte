<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_yi0s_0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s_yi0s_0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:sign-out-variant" {...props}></Icon>
