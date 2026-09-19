<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iz-wqstbl.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG9j4lk5ZG"><path class="iz-wqstbl"/></mask></defs><path mask="url(#SVG9j4lk5ZG)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:women" {...props}></Icon>
