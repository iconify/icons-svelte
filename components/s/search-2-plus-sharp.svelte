<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4sk38i8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m4sk38i8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:search-2-plus-sharp" {...props}></Icon>
