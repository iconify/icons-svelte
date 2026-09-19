<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unmzjbbfs.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGMifv1brb"><path class="unmzjbbfs"/></mask></defs><path mask="url(#SVGMifv1brb)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:three-three" {...props}></Icon>
