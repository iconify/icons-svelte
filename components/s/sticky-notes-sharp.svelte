<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrw_no2ky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yrw_no2ky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:sticky-notes-sharp" {...props}></Icon>
