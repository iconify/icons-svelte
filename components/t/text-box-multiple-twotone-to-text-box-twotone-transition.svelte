<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw1iew.css';
import '../../css/j/j6sn3x.css';
import '../../css/h/hrkd6c.css';
import '../../css/d/d-0mee5h.css';
import '../../css/d/d-r5jj3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iw1iew j6sn3x"/><path class="hrkd6c iw1iew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:text-box-multiple-twotone-to-text-box-twotone-transition" {...props}></Icon>
