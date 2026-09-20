<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zabbtyb5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zabbtyb5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:three-dots-horizontal-in-rectangle" {...props}></Icon>
