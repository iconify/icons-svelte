<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxewg8z1p.css';
import '../../css/t/t08ue7k0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wxewg8z1p"/><path class="t08ue7k0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:travis" {...props}></Icon>
