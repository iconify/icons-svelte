<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxpgx8bbz.css';
import '../../css/p/plw4n8b9a.css';
import '../../css/z/zu45hdb1f.css';
import '../../css/y/yj9rp25pc.css';
import '../../css/u/u080qgbrm.css';
import '../../css/g/glrmtpy1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="lxpgx8bbz"/><path class="plw4n8b9a"/><path class="zu45hdb1f"/><path class="yj9rp25pc"/><path class="u080qgbrm"/><path class="glrmtpy1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:unifiedmodelinglanguage-wordmark" {...props}></Icon>
