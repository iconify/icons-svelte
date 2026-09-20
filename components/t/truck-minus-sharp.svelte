<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6a7f-bca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i6a7f-bca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:truck-minus-sharp" {...props}></Icon>
