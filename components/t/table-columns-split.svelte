<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ib495to2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ib495to2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:table-columns-split" {...props}></Icon>
