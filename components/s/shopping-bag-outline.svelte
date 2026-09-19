<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_9m_3b3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="g_9m_3b3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:shopping-bag-outline" {...props}></Icon>
