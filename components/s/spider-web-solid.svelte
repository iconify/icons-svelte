<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hh24xeqxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hh24xeqxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:spider-web-solid" {...props}></Icon>
