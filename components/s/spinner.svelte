<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eo74jw5my.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eo74jw5my"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:spinner" {...props}></Icon>
