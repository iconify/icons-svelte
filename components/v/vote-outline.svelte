<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vb9su6z-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vb9su6z-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:vote-outline" {...props}></Icon>
