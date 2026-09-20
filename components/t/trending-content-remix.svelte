<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o23e6_bfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="o23e6_bfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:trending-content-remix" {...props}></Icon>
