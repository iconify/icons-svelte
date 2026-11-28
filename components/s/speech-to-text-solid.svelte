<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugr2cuw1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ugr2cuw1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:speech-to-text-solid" {...props}></Icon>
