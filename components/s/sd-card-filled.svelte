<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdsb_nbjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tdsb_nbjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:sd-card-filled" {...props}></Icon>
