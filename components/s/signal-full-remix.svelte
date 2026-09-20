<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmpdv0f8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xmpdv0f8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:signal-full-remix" {...props}></Icon>
