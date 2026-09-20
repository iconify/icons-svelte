<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qddxtrr9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qddxtrr9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:skull" {...props}></Icon>
