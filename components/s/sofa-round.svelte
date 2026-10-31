<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8-4x2b9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h8-4x2b9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:sofa-round" {...props}></Icon>
