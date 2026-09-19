<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/o/oo_vs07_g.css';
import '../../css/a/a-kumkb6u.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGHDswCe1v"><g class="ufeehvblu"><path class="oo_vs07_g"/><path class="a-kumkb6u"/></g></mask></defs><path mask="url(#SVGHDswCe1v)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:sliding-horizontal" {...props}></Icon>
