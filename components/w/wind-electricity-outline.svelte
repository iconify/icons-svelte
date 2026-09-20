<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcauxd15s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kcauxd15s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:wind-electricity-outline" {...props}></Icon>
