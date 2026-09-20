<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iws_6ib4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="iws_6ib4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:script-2-remix" {...props}></Icon>
