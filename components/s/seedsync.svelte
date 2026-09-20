<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwr8mbc3j.css';
import '../../css/s/sl0sqdbfa.css';
import '../../css/w/w5mozcc8a.css';
import '../../css/o/om93iibmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vwr8mbc3j"/><path class="sl0sqdbfa"/><path class="w5mozcc8a"/><path class="om93iibmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:seedsync" {...props}></Icon>
