<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8qwtlv5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="q8qwtlv5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:spotify-remix" {...props}></Icon>
