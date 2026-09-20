<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hax53gbsh.css';
import '../../css/h/hb4lzh0lj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hax53gbsh"/><path class="hb4lzh0lj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:trophy-circle-fill" {...props}></Icon>
