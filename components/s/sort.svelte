<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xo-h30yov.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGAj84feQA"><path class="xo-h30yov"/></mask></defs><path mask="url(#SVGAj84feQA)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:sort" {...props}></Icon>
