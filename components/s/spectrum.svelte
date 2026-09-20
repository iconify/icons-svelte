<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xp1vsobks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xp1vsobks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:spectrum" {...props}></Icon>
