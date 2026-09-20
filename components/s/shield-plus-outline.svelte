<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/suxtayb_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="suxtayb_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:shield-plus-outline" {...props}></Icon>
