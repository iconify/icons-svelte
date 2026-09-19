<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0_9m3btv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1600,"height":1792};
const content = `<path class="s0_9m3btv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:snowflake-o" {...props}></Icon>
