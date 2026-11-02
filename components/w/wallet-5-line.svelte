<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_vh1abtm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c_vh1abtm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:wallet-5-line" {...props}></Icon>
