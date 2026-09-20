<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uecfotbfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="uecfotbfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:smileys-sad" {...props}></Icon>
