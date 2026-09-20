<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aedcft.css';
import '../../css/c/chdxye.css';
import '../../css/f/fill-to-0.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/s/so-from-34.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aedcft"/><path class="chdxye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:star-half-twotone" {...props}></Icon>
