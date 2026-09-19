<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/y/yeo4tvbtv.css';
import '../../css/a/ag8htpbhv.css';
import '../../css/j/jnko8r0hc.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGMa86wdcE"><g class="s9cl3zbei"><path class="yeo4tvbtv"/><circle class="ag8htpbhv"/><path class="jnko8r0hc"/></g></mask></defs><path mask="url(#SVGMa86wdcE)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:watch-one" {...props}></Icon>
