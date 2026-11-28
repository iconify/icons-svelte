<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-n5xbbur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z-n5xbbur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:waveform-medium-solid" {...props}></Icon>
