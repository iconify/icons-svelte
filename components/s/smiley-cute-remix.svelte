<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4og9jlue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="k4og9jlue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:smiley-cute-remix" {...props}></Icon>
