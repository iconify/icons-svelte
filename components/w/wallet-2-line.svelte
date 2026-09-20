<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nax9wcbnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nax9wcbnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:wallet-2-line" {...props}></Icon>
