<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkvkheb0s.css';
import '../../css/c/ci5ggcbfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bkvkheb0s"/><path class="ci5ggcbfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:smartphone-nfc-filled" {...props}></Icon>
