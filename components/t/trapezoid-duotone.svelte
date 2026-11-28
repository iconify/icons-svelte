<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isg9b6-va.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="isg9b6-va primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:trapezoid-duotone" {...props}></Icon>
