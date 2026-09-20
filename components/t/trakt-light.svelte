<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/no2_z4syg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="no2_z4syg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:trakt-light" {...props}></Icon>
