<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9kn9pbtw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="t9kn9pbtw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:share-alt-filled" {...props}></Icon>
