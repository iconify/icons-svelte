<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gopnm44um.css';
import '../../css/r/r4eo4kcpj.css';
import '../../css/s/sxv5582gx.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGA1BlOboC"><g class="gopnm44um"><path class="r4eo4kcpj"/><path class="sxv5582gx"/></g></mask></defs><path mask="url(#SVGA1BlOboC)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:ticket-one" {...props}></Icon>
