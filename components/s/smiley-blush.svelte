<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2ztgtcnl.css';
import '../../css/o/omzx56fzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v2ztgtcnl"/><path class="omzx56fzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:smiley-blush" {...props}></Icon>
