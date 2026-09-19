<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwvp95byt.css';
import '../../css/l/l8-7_vbmo.css';
import '../../css/v/vn2loybei.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGSqD1uCIk"><g class="wwvp95byt"><rect class="l8-7_vbmo"/><path class="vn2loybei"/></g></mask></defs><path mask="url(#SVGSqD1uCIk)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:scan-setting" {...props}></Icon>
