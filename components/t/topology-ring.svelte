<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/huqn5m_ey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="huqn5m_ey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:topology-ring" {...props}></Icon>
