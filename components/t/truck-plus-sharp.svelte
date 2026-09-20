<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ih812rfac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ih812rfac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:truck-plus-sharp" {...props}></Icon>
