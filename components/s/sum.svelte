<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4xorccrs.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGgtGe9uAZ"><path class="h4xorccrs"/></mask></defs><path mask="url(#SVGgtGe9uAZ)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:sum" {...props}></Icon>
