<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xeb6ks00l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xeb6ks00l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:satoshi-v1-filled" {...props}></Icon>
