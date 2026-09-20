<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1tyi1bfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s1tyi1bfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:typhoon-fill" {...props}></Icon>
