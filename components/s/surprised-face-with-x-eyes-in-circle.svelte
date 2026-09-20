<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-__qo4vr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="p-__qo4vr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:surprised-face-with-x-eyes-in-circle" {...props}></Icon>
