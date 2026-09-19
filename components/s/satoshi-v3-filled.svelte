<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jed186bsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jed186bsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:satoshi-v3-filled" {...props}></Icon>
