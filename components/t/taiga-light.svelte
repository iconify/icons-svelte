<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s90tedchv.css';
import '../../css/j/jdpagb2-o.css';
import '../../css/m/mam2srhpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s90tedchv"/><path class="jdpagb2-o"/><path class="mam2srhpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:taiga-light" {...props}></Icon>
