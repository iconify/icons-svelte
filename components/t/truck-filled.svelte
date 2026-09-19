<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8or18b7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u8or18b7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:truck-filled" {...props}></Icon>
