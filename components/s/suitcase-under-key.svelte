<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhwbn-bgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yhwbn-bgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:suitcase-under-key" {...props}></Icon>
