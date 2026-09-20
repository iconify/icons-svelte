<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-e96896z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="x-e96896z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:sort-descending-remix" {...props}></Icon>
