<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ck4m_fflq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ck4m_fflq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:text-indent" {...props}></Icon>
