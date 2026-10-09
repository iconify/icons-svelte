<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sy8iuubej.css';
import '../../css/y/yc11i_vei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sy8iuubej"/><path class="yc11i_vei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:thumbs-up-20" {...props}></Icon>
