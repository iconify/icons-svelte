<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8ckk_crr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="r8ckk_crr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:space-between-vertically" {...props}></Icon>
