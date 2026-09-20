<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6qqye7ob.css';
import '../../css/o/oxdpjjuzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m6qqye7ob"/><path class="oxdpjjuzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:whistle-line" {...props}></Icon>
