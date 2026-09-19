<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lyep9hjio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lyep9hjio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:toilet-filled" {...props}></Icon>
