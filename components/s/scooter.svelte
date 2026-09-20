<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wlvs94qcj.css';
import '../../css/a/af5wgxf3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wlvs94qcj"/><path class="af5wgxf3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:scooter" {...props}></Icon>
