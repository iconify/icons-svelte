<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/juntpgr-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="juntpgr-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:vip-crown-2-fill" {...props}></Icon>
