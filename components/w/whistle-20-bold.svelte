<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtw_wzb8t.css';
import '../../css/g/gseyqnbcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qtw_wzb8t"/><path class="gseyqnbcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:whistle-20-bold" {...props}></Icon>
