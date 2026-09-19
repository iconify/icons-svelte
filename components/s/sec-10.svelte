<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_ozbwbzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":384};
const content = `<path class="m_ozbwbzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:sec-10" {...props}></Icon>
