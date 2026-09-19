<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w00s2nbjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="w00s2nbjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:user-astronaut" {...props}></Icon>
