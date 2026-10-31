<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezzw99brc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ezzw99brc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:triangle-info-round" {...props}></Icon>
