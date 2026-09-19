<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/md3_ln_5j.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGWg8t6c8U"><path class="md3_ln_5j"/></mask></defs><path mask="url(#SVGWg8t6c8U)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:twitter" {...props}></Icon>
