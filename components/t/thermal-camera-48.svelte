<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zncj9xbho.css';
import '../../css/j/j2czn_mgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zncj9xbho"/><path class="j2czn_mgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:thermal-camera-48" {...props}></Icon>
