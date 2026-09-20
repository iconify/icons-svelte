<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqzom5m_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lqzom5m_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:subtitle-filled" {...props}></Icon>
