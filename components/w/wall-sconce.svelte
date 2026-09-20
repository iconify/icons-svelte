<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/se80d2bif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="se80d2bif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:wall-sconce" {...props}></Icon>
