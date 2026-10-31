<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3n9zob-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="t3n9zob-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:view-split-20-solid" {...props}></Icon>
