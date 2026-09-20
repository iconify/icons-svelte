<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2p_l-b6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b2p_l-b6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:service-fill" {...props}></Icon>
