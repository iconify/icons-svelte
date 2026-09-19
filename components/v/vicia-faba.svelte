<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/s/sdoteibvg.css';
import '../../css/m/mcdf-5f6l.css';
import '../../css/b/b1f263bkh.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGvzxhLcCT"><g class="ufeehvblu"><path class="sdoteibvg"/><path class="mcdf-5f6l"/><path class="b1f263bkh"/></g></mask></defs><path mask="url(#SVGvzxhLcCT)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:vicia-faba" {...props}></Icon>
