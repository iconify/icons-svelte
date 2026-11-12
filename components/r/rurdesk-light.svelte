<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwwaekbrn.css';
import '../../css/a/a-4ue5bby.css';
import '../../css/t/tm45hz_di.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pwwaekbrn"/><path class="a-4ue5bby"/><circle class="tm45hz_di"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rurdesk-light" {...props}></Icon>
