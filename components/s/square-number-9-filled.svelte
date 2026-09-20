<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhv7_-hzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yhv7_-hzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-number-9-filled" {...props}></Icon>
