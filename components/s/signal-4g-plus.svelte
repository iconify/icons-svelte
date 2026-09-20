<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgxa4cbke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fgxa4cbke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:signal-4g-plus" {...props}></Icon>
