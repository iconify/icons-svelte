<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqlsd2b2r.css';
import '../../css/a/aepwucb-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tqlsd2b2r"/><path class="aepwucb-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:speech-filled" {...props}></Icon>
