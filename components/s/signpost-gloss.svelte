<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ico_k8sza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ico_k8sza wm-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:signpost-gloss" {...props}></Icon>
