<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vz9_7etcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vz9_7etcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:threads-solid" {...props}></Icon>
