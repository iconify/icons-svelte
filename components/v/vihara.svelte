<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xejpd7b6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="xejpd7b6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:vihara" {...props}></Icon>
