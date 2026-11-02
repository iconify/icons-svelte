<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wiqcku4-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wiqcku4-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:snowflake-line" {...props}></Icon>
