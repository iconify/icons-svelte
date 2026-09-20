<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_vskm2fc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m_vskm2fc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:sidebar-alt-solid" {...props}></Icon>
