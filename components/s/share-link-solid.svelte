<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gc6ozldmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gc6ozldmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:share-link-solid" {...props}></Icon>
