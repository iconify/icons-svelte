<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/ql0phr9-d.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGkWEIQcHM"><path class="ql0phr9-d"/></mask></defs><path mask="url(#SVGkWEIQcHM)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:tiktok" {...props}></Icon>
