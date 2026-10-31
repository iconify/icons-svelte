<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trtb5yb5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="trtb5yb5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:snowflake-duotone-round" {...props}></Icon>
