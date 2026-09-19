<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ec-8ohbed.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGRWh4Mdhm"><path class="ec-8ohbed"/></mask></defs><path mask="url(#SVGRWh4Mdhm)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:triangle-round-rectangle" {...props}></Icon>
