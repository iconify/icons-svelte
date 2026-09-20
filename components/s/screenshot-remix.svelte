<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tly6u8byv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="tly6u8byv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:screenshot-remix" {...props}></Icon>
