<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2u9f_tut.css';
import '../../css/e/ezgs73y2p.css';
import '../../css/z/ze96stecn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="n2u9f_tut"/><path class="ezgs73y2p"/><path class="ze96stecn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rugby-48" {...props}></Icon>
