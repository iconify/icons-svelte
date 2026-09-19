<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmc733baq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="hmc733baq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:ui-zoom-outline" {...props}></Icon>
