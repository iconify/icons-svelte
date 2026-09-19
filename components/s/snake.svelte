<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eevefobbg.css';
import '../../css/v/vh_x9ccjq.css';
import '../../css/b/bku4shbfc.css';
import '../../css/l/lob6lbb2k.css';
import '../../css/g/gbkh3v4as.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eevefobbg"/><path class="vh_x9ccjq"/><path class="bku4shbfc"/><path class="lob6lbb2k"/><circle class="gbkh3v4as"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:snake" {...props}></Icon>
