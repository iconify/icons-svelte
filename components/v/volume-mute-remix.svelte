<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cz2h6vkvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cz2h6vkvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:volume-mute-remix" {...props}></Icon>
