<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okz8j0hfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="okz8j0hfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-split-vertical-filled" {...props}></Icon>
