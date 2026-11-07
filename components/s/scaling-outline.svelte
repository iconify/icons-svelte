<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_wdj5b3k.css';
import '../../css/t/t4y5-pbqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m_wdj5b3k"/><path class="t4y5-pbqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:scaling-outline" {...props}></Icon>
