<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwsaykppo.css';
import '../../css/a/afpdyh0xp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lwsaykppo"/><path class="afpdyh0xp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:thor" {...props}></Icon>
