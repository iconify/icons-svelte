<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aykwv9b4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="aykwv9b4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:send-outline" {...props}></Icon>
