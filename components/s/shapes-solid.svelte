<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f7_41vbux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f7_41vbux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:shapes-solid" {...props}></Icon>
