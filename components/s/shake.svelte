<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/a/a3egu4bnj.css';
import '../../css/k/k_94f0bqu.css';
import '../../css/z/zri7a6b5o.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGagp6hcaK"><g class="v3_i3wktz"><path class="a3egu4bnj"/><path class="k_94f0bqu"/><path class="zri7a6b5o"/></g></mask></defs><path mask="url(#SVGagp6hcaK)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:shake" {...props}></Icon>
