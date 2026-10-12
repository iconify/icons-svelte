<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxcw1zbpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fxcw1zbpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:thermometer-snowflake-filled" {...props}></Icon>
