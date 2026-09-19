<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zfjz56b-b.css';
import '../../css/v/vhmqj7bwp.css';
import '../../css/r/rhfc70guf.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG89Y2hdoo"><g class="ft5dv1b6b"><path class="zfjz56b-b"/><path class="vhmqj7bwp"/><path clip-rule="evenodd" class="rhfc70guf"/></g></mask></defs><path mask="url(#SVG89Y2hdoo)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:sofa-two" {...props}></Icon>
