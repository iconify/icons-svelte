<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ha9i3i5iw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ha9i3i5iw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:street-sign-remix" {...props}></Icon>
