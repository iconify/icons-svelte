<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/km8wd_zes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="km8wd_zes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:sbt" {...props}></Icon>
