<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxqvff8os.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="vxqvff8os"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:temple-alt2x-outline" {...props}></Icon>
