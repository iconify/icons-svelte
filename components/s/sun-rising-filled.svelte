<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_pp8kb8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x_pp8kb8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:sun-rising-filled" {...props}></Icon>
