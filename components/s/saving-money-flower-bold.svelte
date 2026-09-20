<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7s431bhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d7s431bhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:saving-money-flower-bold" {...props}></Icon>
