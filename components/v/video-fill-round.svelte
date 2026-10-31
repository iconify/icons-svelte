<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvv0n5b3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gvv0n5b3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:video-fill-round" {...props}></Icon>
