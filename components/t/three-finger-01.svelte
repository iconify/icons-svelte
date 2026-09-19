<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_85a_4sf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l_85a_4sf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:three-finger-01" {...props}></Icon>
