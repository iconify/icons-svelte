<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aij4m_rjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="aij4m_rjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:ussunnah" {...props}></Icon>
