<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhn645b3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qhn645b3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:toyota" {...props}></Icon>
