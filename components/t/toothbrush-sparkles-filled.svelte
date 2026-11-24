<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfctapahl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mfctapahl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:toothbrush-sparkles-filled" {...props}></Icon>
