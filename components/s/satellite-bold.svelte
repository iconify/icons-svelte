<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mh0vd8g8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mh0vd8g8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:satellite-bold" {...props}></Icon>
