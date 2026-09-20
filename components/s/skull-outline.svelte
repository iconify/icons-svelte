<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8-qn0b6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="t8-qn0b6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:skull-outline" {...props}></Icon>
