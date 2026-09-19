<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbl-y_rlh.css';
import '../../css/x/xxl63pf9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="mbl-y_rlh"/><path class="xxl63pf9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:translate" {...props}></Icon>
