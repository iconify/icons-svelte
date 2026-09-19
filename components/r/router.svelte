<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/r8rpadpnu.css';
import '../../css/l/la2xe_bme.css';
import '../../css/w/wkl_labxn.css';
import '../../css/u/uyve4wbpr.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGAPhOHbkU"><g class="ft5dv1b6b"><rect class="r8rpadpnu"/><path class="la2xe_bme"/><rect class="wkl_labxn"/><path class="uyve4wbpr"/></g></mask></defs><path mask="url(#SVGAPhOHbkU)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:router" {...props}></Icon>
