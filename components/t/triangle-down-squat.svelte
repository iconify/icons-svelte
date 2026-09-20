<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mh2xf-bha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mh2xf-bha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:triangle-down-squat" {...props}></Icon>
