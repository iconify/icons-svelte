<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/q/qaw7rbkbp.css';
import '../../css/c/cjkvecb0a.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGHRF2iexP"><g class="aql7dnt-u"><rect transform="rotate(45 24.762 3.243)" class="qaw7rbkbp"/><path class="cjkvecb0a"/></g></mask></defs><path mask="url(#SVGHRF2iexP)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:tray" {...props}></Icon>
