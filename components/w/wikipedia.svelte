<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iycln-b8i.css';
import '../../css/m/mb76b6m0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="iycln-b8i"/><path class="mb76b6m0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wikipedia" {...props}></Icon>
