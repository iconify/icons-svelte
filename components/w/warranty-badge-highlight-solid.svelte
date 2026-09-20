<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xp06x116o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xp06x116o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:warranty-badge-highlight-solid" {...props}></Icon>
