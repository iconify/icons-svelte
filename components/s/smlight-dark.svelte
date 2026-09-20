<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4pkyxbyo.css';
import '../../css/j/j34xgl0mc.css';
import '../../css/h/hti6_g1vm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="q4pkyxbyo"/><circle class="j34xgl0mc"/><circle class="hti6_g1vm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:smlight-dark" {...props}></Icon>
