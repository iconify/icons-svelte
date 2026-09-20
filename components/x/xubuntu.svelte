<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpxp0oysk.css';
import '../../css/l/l6_aktb5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="vpxp0oysk"/><path class="l6_aktb5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:xubuntu" {...props}></Icon>
