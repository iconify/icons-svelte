<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sducl6b4p.css';
import '../../css/r/rvcp9fbuk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sducl6b4p"/><path class="rvcp9fbuk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:snapmaker" {...props}></Icon>
