<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvqvdrb6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cvqvdrb6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:shield-crown" {...props}></Icon>
