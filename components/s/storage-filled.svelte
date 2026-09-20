<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6ngtbcis.css';
import '../../css/k/k5o2fzblv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c6ngtbcis"/><path clip-rule="evenodd" class="k5o2fzblv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:storage-filled" {...props}></Icon>
