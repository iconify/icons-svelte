<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pe9nqr8no.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pe9nqr8no"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:shield-sparkle-fill-round" {...props}></Icon>
