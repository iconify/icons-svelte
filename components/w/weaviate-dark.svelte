<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lnenk_b6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lnenk_b6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:weaviate-dark" {...props}></Icon>
