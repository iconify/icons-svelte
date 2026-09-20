<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qj6rrdcag.css';
import '../../css/z/zzefkb6jx.css';
import '../../css/o/oo4e5ubpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qj6rrdcag"/><path class="zzefkb6jx"/><path class="oo4e5ubpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:vidya" {...props}></Icon>
