<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p04wurlsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p04wurlsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:verify-filled" {...props}></Icon>
