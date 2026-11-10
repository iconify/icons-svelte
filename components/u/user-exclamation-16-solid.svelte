<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8286fbmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="w8286fbmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:user-exclamation-16-solid" {...props}></Icon>
