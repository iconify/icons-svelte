<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwd45ta4x.css';
import '../../css/x/xjwgdc_uw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vwd45ta4x"/><path clip-rule="evenodd" class="xjwgdc_uw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:vault-filled" {...props}></Icon>
