<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m11cagbqy.css';
import '../../css/t/tjmji5h6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m11cagbqy"/><path class="tjmji5h6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:swagger" {...props}></Icon>
