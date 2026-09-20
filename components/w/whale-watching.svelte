<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5pk8r8ai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="x5pk8r8ai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:whale-watching" {...props}></Icon>
