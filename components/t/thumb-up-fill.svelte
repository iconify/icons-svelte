<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/ver42fbjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ver42fbjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:thumb-up-fill" {...props}></Icon>
