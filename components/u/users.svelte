<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxc7bsk8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wxc7bsk8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:users" {...props}></Icon>
