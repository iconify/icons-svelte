<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_hbxdkvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="m_hbxdkvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:signal-full" {...props}></Icon>
