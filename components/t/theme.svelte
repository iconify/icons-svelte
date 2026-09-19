<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxs2uuwtx.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGpdd17cBw"><path class="fxs2uuwtx"/></mask></defs><path mask="url(#SVGpdd17cBw)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:theme" {...props}></Icon>
