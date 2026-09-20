<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9g4-upkk.css';
import '../../css/o/o4kdtcbtb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i9g4-upkk"/><path class="o4kdtcbtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:scons" {...props}></Icon>
