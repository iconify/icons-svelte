<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcibg-4yl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pcibg-4yl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:some-google" {...props}></Icon>
