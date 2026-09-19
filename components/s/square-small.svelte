<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ppbk3zbaq.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGve42mdIb"><path class="ppbk3zbaq"/></mask></defs><path mask="url(#SVGve42mdIb)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:square-small" {...props}></Icon>
