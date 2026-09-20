<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fehezhbes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fehezhbes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:rounded-square-outline-with-dot" {...props}></Icon>
