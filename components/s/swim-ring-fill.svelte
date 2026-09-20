<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uatr2mb4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uatr2mb4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:swim-ring-fill" {...props}></Icon>
