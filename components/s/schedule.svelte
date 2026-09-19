<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv130ab-t.css';
import '../../css/z/zbz6fmbfq.css';
import '../../css/p/pt3ta8bfq.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGS7p27dQv"><g class="hv130ab-t"><rect class="zbz6fmbfq"/><path class="pt3ta8bfq"/></g></mask></defs><path mask="url(#SVGS7p27dQv)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:schedule" {...props}></Icon>
