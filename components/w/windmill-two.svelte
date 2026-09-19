<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p00jiub_r.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGlzn6oczD"><path class="p00jiub_r"/></mask></defs><path mask="url(#SVGlzn6oczD)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:windmill-two" {...props}></Icon>
