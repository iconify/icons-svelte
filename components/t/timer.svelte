<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vddpwlbxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vddpwlbxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:timer" {...props}></Icon>
