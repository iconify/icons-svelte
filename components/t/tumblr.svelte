<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tcgz-8zfs.css';
import '../../css/e/e7nh98xpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="tcgz-8zfs"/><path class="e7nh98xpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tumblr" {...props}></Icon>
