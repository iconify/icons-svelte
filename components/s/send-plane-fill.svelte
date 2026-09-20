<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w98n7s1pu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w98n7s1pu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:send-plane-fill" {...props}></Icon>
