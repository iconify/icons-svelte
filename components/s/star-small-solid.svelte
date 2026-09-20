<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmr3fxbye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dmr3fxbye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:star-small-solid" {...props}></Icon>
