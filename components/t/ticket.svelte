<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0wn-wuie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s0wn-wuie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:ticket" {...props}></Icon>
