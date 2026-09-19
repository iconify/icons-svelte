<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajsz_kbop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":488};
const content = `<path class="ajsz_kbop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:whatsapp" {...props}></Icon>
