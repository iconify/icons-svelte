<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/peejlwbeb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="peejlwbeb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:scan-face-solid" {...props}></Icon>
