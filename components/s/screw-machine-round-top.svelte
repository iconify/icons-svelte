<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c88zfpbbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c88zfpbbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:screw-machine-round-top" {...props}></Icon>
