<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eop8onyec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eop8onyec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:signpost-fill-round" {...props}></Icon>
