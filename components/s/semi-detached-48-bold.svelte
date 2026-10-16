<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdn7143ls.css';
import '../../css/k/kr6gu5bwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tdn7143ls"/><path class="kr6gu5bwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:semi-detached-48-bold" {...props}></Icon>
