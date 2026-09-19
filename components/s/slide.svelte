<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/j/jzb3v_12p.css';
import '../../css/u/upfqr38kf.css';
import '../../css/i/ip9rf3bsv.css';
import '../../css/x/xfkdr6b7l.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGy38Vyesv"><g class="ufeehvblu"><path class="jzb3v_12p"/><path class="upfqr38kf"/><path class="ip9rf3bsv"/><path class="xfkdr6b7l"/></g></mask></defs><path mask="url(#SVGy38Vyesv)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:slide" {...props}></Icon>
