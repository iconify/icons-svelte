<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihgmx3brz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ihgmx3brz primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:semaphore-vertical-duotone" {...props}></Icon>
