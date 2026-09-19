<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/k/knrsqtfts.css';
import '../../css/q/qp71o_xbh.css';
import '../../css/r/rvsjambol.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGrFFZMe2p"><g class="s9cl3zbei"><circle class="knrsqtfts"/><path class="qp71o_xbh"/><path class="rvsjambol"/></g></mask></defs><path mask="url(#SVGrFFZMe2p)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:timer" {...props}></Icon>
