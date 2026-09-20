<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tn8fv0bej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tn8fv0bej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:unlock-outline" {...props}></Icon>
