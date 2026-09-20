<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5mzdhlgm.css';
import '../../css/w/wjafqsbeh.css';
import '../../css/s/s9be24r1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c5mzdhlgm"/><path class="wjafqsbeh"/><path class="s9be24r1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:threadfin" {...props}></Icon>
