<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc2xykbod.css';
import '../../css/z/zid7xkcmh.css';
import '../../css/t/tih4hqb3l.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGvF4cycZm"><g class="bc2xykbod"><rect class="zid7xkcmh"/><rect class="tih4hqb3l"/></g></mask></defs><path mask="url(#SVGvF4cycZm)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:zero-key" {...props}></Icon>
