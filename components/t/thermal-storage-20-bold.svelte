<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/druapyb0f.css';
import '../../css/p/psdm-j5hl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="druapyb0f"/><path class="psdm-j5hl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:thermal-storage-20-bold" {...props}></Icon>
