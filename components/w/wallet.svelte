<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m80_ws04e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m80_ws04e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:wallet" {...props}></Icon>
