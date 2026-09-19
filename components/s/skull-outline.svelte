<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmp9ddbhf.css';
import '../../css/k/kewmiqbmw.css';
import '../../css/d/dp4rysb_i.css';
import '../../css/m/mclf1pryu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pmp9ddbhf"/><circle class="kewmiqbmw"/><circle class="dp4rysb_i"/><path class="mclf1pryu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:skull-outline" {...props}></Icon>
