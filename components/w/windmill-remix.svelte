<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncfoy5-4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ncfoy5-4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:windmill-remix" {...props}></Icon>
