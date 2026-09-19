<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9245d6ei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1025};
const content = `<path class="h9245d6ei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:shuttle" {...props}></Icon>
