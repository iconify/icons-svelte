<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a21bjysuj.css';
import '../../css/t/tm-9qcpcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="a21bjysuj"/><path class="tm-9qcpcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:scrypted" {...props}></Icon>
