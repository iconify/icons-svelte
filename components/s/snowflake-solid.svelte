<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3_sikb1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x3_sikb1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:snowflake-solid" {...props}></Icon>
