<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_o-pzkhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s_o-pzkhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:swap-fill" {...props}></Icon>
