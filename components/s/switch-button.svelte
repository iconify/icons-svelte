<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/d/dn_y4s9cj.css';
import '../../css/l/ly3952sva.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGxi7i2kST"><g class="ufeehvblu"><path class="dn_y4s9cj"/><path class="ly3952sva"/></g></mask></defs><path mask="url(#SVGxi7i2kST)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:switch-button" {...props}></Icon>
