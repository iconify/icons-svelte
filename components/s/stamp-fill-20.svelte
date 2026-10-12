<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktay6hbmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ktay6hbmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:stamp-fill-20" {...props}></Icon>
