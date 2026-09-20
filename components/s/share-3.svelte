<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oas4cbcex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oas4cbcex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:share-3" {...props}></Icon>
