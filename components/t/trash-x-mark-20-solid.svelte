<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wn9bxqalx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="wn9bxqalx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:trash-x-mark-20-solid" {...props}></Icon>
