<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpr85zb3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qpr85zb3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:triangle-outline" {...props}></Icon>
