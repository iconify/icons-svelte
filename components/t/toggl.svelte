<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vt_7kd49m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vt_7kd49m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:toggl" {...props}></Icon>
