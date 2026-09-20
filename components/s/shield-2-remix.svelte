<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvrr6-blq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="gvrr6-blq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:shield-2-remix" {...props}></Icon>
