<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/onraaob_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="onraaob_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:screen-alt-outline" {...props}></Icon>
