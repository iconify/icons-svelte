<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/econho.css';
import '../../css/i/iw1iew.css';
import '../../css/b/b92-iz.css';
import '../../css/d/d-3gok0n.css';
import '../../css/d/d-5rxztz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="econho iw1iew"/><path class="b92-iz iw1iew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:text-box-twotone-to-text-box-multiple-twotone-transition" {...props}></Icon>
