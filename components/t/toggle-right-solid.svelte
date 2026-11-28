<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vysygrdiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vysygrdiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:toggle-right-solid" {...props}></Icon>
