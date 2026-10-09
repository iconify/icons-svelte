<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5vpx869x.css';
import '../../css/c/cjykg8bjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r5vpx869x"/><path class="cjykg8bjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:subsea-cable-48" {...props}></Icon>
