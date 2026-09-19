<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lh-p_ha-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lh-p_ha-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mono-icons:sun" {...props}></Icon>
