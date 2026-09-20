<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4415cjyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l4415cjyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:windows-defender-2016-dark" {...props}></Icon>
