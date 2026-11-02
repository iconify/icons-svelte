<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlwbs1dqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vlwbs1dqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:user-warning-line" {...props}></Icon>
