<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ud2q-obza.css';
import '../../css/z/zb7vgmb5u.css';
import '../../css/u/uywxzgm7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ud2q-obza"/><path class="zb7vgmb5u"/><path class="uywxzgm7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:watchtower-dark" {...props}></Icon>
