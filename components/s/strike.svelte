<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgnflcc0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":700,"height":707};
const content = `<path class="rgnflcc0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:strike" {...props}></Icon>
