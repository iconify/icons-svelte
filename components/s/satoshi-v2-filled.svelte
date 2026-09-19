<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6ltt5byn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o6ltt5byn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:satoshi-v2-filled" {...props}></Icon>
