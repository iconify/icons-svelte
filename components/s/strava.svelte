<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/asnjkubhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="asnjkubhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:strava" {...props}></Icon>
