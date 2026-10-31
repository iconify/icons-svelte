<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pc-glxx-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pc-glxx-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:thumbs-down-fill-round" {...props}></Icon>
