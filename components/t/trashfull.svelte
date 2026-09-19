<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufp99g8_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="ufp99g8_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:trashfull" {...props}></Icon>
