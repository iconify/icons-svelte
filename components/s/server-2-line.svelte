<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmfredbtg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jmfredbtg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:server-2-line" {...props}></Icon>
