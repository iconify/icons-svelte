<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-7zdubzz.css';
import '../../css/j/jjj7yd_xu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u-7zdubzz"/><path class="jjj7yd_xu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:software" {...props}></Icon>
