<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wap7h8uas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wap7h8uas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:ticket-filled" {...props}></Icon>
