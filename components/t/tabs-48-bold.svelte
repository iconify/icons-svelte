<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_nfahbsi.css';
import '../../css/p/py667bcgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="d_nfahbsi"/><path class="py667bcgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tabs-48-bold" {...props}></Icon>
