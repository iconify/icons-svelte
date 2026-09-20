<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnq988bcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gnq988bcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:snowflake-melt" {...props}></Icon>
