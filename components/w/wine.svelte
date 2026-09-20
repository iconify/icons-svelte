<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ph89agb5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ph89agb5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:wine" {...props}></Icon>
