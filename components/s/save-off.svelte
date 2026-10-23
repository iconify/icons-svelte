<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/huibr8etf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="huibr8etf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:save-off" {...props}></Icon>
