<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0mqs8vsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m0mqs8vsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:skip-back-solid" {...props}></Icon>
