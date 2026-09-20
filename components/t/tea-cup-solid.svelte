<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kc_6r3r6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kc_6r3r6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:tea-cup-solid" {...props}></Icon>
