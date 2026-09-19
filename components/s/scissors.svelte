<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwvp95byt.css';
import '../../css/l/l8-7_vbmo.css';
import '../../css/y/yswwq9bkb.css';
import '../../css/b/b8g26fbwk.css';
import '../../css/t/tdn52fmgf.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGLgbNBAjV"><g class="wwvp95byt"><rect class="l8-7_vbmo"/><path class="yswwq9bkb"/><circle class="b8g26fbwk"/><circle class="tdn52fmgf"/></g></mask></defs><path mask="url(#SVGLgbNBAjV)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:scissors" {...props}></Icon>
