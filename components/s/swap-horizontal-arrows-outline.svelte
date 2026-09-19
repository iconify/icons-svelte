<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_cx-qbkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":25};
const content = `<path clip-rule="evenodd" class="m_cx-qbkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:swap-horizontal-arrows-outline" {...props}></Icon>
