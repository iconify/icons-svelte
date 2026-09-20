<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fk1z-bb0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fk1z-bb0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:truck-arrow-down-sharp" {...props}></Icon>
