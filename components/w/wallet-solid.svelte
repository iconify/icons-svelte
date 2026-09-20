<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/byw7okbvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="byw7okbvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:wallet-solid" {...props}></Icon>
