<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jf69e7b9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jf69e7b9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:scrypted-dark" {...props}></Icon>
