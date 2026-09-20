<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4uurfb5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="g4uurfb5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:watchtower-castle-solid" {...props}></Icon>
