<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/y/ytep93bao.css';
import '../../css/j/j5_2do9_g.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGPoxM4bnA"><g class="ufeehvblu"><path class="ytep93bao"/><path class="j5_2do9_g"/></g></mask></defs><path mask="url(#SVGPoxM4bnA)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:topic" {...props}></Icon>
