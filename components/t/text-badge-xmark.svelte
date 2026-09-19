<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lc9wtibdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="lc9wtibdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:text-badge-xmark" {...props}></Icon>
