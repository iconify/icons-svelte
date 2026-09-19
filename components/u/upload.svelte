<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lymv1xkrn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lymv1xkrn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:upload" {...props}></Icon>
