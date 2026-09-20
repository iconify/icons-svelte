<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jopy93b_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jopy93b_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:snowflake-temperature" {...props}></Icon>
