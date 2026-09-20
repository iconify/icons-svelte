<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hm8y5cbhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hm8y5cbhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:yahoo-fill" {...props}></Icon>
