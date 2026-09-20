<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fz9c80bio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fz9c80bio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:tune-adjust-volume-remix" {...props}></Icon>
