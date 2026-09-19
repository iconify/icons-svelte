<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwvp95byt.css';
import '../../css/u/ux3vkrb2f.css';
import '../../css/z/zs3kp5bcb.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGlE2NyucQ"><g class="wwvp95byt"><path clip-rule="evenodd" class="ux3vkrb2f"/><path class="zs3kp5bcb"/></g></mask></defs><path mask="url(#SVGlE2NyucQ)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:water-rate-two" {...props}></Icon>
