<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsqgj0_wr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nsqgj0_wr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:triangle-flag-circle" {...props}></Icon>
