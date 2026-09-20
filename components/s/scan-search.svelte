<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rka33acyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rka33acyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:scan-search" {...props}></Icon>
