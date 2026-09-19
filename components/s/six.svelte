<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xh8js1bkv.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGVm4YwdnW"><path class="xh8js1bkv"/></mask></defs><path mask="url(#SVGVm4YwdnW)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:six" {...props}></Icon>
