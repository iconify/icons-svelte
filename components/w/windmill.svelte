<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enq8bzvvs.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGRJXwnbaw"><path clip-rule="evenodd" class="enq8bzvvs"/></mask></defs><path mask="url(#SVGRJXwnbaw)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:windmill" {...props}></Icon>
