<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3bnzidss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q3bnzidss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:select-drag" {...props}></Icon>
