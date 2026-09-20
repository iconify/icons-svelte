<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7i3eac_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="z7i3eac_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:surveillance-camera-remix" {...props}></Icon>
