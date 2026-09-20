<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f156abbyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="f156abbyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:signage-pedestrian-no-crossing-remix" {...props}></Icon>
