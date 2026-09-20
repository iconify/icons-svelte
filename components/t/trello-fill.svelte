<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vq5iey98t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vq5iey98t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:trello-fill" {...props}></Icon>
