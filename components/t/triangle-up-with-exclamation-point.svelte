<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x16itb56c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="x16itb56c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:triangle-up-with-exclamation-point" {...props}></Icon>
