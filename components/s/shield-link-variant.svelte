<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pe1qa4bti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pe1qa4bti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:shield-link-variant" {...props}></Icon>
