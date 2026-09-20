<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tc4-bsb_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tc4-bsb_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:share-16" {...props}></Icon>
