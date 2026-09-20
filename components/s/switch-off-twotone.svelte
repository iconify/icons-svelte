<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uk8z0l.css';
import '../../css/y/ydovum.css';
import '../../css/u/uu_2ij.css';
import '../../css/f/fill-to-0.css';
import '../../css/s/so-from-54.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/f/fade-to-1.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uk8z0l ydovum"/><circle class="uu_2ij ydovum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:switch-off-twotone" {...props}></Icon>
