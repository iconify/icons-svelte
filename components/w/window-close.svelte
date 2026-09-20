<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gks8du_si.css';
import '../../css/s/sceipoxjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gks8du_si"/><path class="sceipoxjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:window-close" {...props}></Icon>
