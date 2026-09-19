<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqiu88m_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zqiu88m_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:user-scan" {...props}></Icon>
