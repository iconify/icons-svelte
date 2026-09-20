<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntnxv4bnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ntnxv4bnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:ticket-sale-filled" {...props}></Icon>
