<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4_-n21gr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v4_-n21gr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:square-padding-solid" {...props}></Icon>
