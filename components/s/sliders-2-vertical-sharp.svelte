<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8d7f8bej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x8d7f8bej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:sliders-2-vertical-sharp" {...props}></Icon>
