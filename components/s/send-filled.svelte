<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mcoda5bjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mcoda5bjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:send-filled" {...props}></Icon>
