<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eckincbby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eckincbby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:send-square4-filled" {...props}></Icon>
