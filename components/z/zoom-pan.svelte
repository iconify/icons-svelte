<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwtn5pbne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rwtn5pbne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:zoom-pan" {...props}></Icon>
