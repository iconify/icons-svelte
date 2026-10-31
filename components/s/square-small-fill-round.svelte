<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/klo0mm2kn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="klo0mm2kn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:square-small-fill-round" {...props}></Icon>
