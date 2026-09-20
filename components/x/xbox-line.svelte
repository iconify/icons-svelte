<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mytw1mb7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mytw1mb7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:xbox-line" {...props}></Icon>
