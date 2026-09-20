<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6kfzrspk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q6kfzrspk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:send-plane-2-line" {...props}></Icon>
