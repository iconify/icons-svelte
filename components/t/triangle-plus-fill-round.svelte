<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6eap6brc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p6eap6brc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:triangle-plus-fill-round" {...props}></Icon>
