<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5fwnfbqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="e5fwnfbqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:save-outline" {...props}></Icon>
