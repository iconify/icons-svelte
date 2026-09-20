<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lv717gnze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lv717gnze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:stop-square-solid" {...props}></Icon>
