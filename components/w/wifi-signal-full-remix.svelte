<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emqywvbmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="emqywvbmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:wifi-signal-full-remix" {...props}></Icon>
