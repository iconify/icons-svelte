<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aw9cobb3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="aw9cobb3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:step-ladder" {...props}></Icon>
