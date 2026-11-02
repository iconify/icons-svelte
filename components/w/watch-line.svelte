<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgz6ohbir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qgz6ohbir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:watch-line" {...props}></Icon>
