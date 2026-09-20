<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1cmtz2bf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="g1cmtz2bf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:tune-adjust-volume-solid" {...props}></Icon>
