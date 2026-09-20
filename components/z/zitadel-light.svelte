<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xst33ez6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xst33ez6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:zitadel-light" {...props}></Icon>
