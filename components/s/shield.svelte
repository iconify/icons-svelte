<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxuy57k1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mxuy57k1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:shield" {...props}></Icon>
