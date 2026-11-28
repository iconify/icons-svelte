<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqz-vvbfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fqz-vvbfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:underline-solid" {...props}></Icon>
