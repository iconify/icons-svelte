<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c58st574x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c58st574x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:size-extra-extra-large" {...props}></Icon>
