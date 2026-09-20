<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0-4vtf0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="g0-4vtf0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:signin-outline" {...props}></Icon>
