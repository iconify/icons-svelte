<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2ooaab7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="e2ooaab7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:warp-squeeze" {...props}></Icon>
