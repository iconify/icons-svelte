<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/a/aemyv_bct.css';
import '../../css/y/yma8que2u.css';
import '../../css/o/oi7oksbqj.css';
import '../../css/k/ky-4twbxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="aemyv_bct"/><circle class="yma8que2u"/><path class="oi7oksbqj"/><path class="ky-4twbxw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:users" {...props}></Icon>
