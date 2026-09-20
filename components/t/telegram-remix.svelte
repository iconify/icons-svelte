<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9qv027_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="i9qv027_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:telegram-remix" {...props}></Icon>
