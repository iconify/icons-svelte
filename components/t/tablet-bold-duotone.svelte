<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drnzps6if.css';
import '../../css/f/fifx41-ph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="drnzps6if"/><path class="fifx41-ph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:tablet-bold-duotone" {...props}></Icon>
