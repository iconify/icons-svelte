<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7ryd22fh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="e7ryd22fh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:zodiac-3-remix" {...props}></Icon>
