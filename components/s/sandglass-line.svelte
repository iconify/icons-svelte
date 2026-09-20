<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3godgbju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o3godgbju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sandglass-line" {...props}></Icon>
