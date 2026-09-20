<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wite9bc0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="wite9bc0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:wave-signal-circle-remix" {...props}></Icon>
