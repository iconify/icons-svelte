<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrbn05bgs.css';
import '../../css/b/boo849bbg.css';
import '../../css/z/zf2mmcbib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nrbn05bgs"/><path class="boo849bbg"/><path class="zf2mmcbib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:sitemap" {...props}></Icon>
