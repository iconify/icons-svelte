<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgk-jqj6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="wgk-jqj6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:target-20-solid" {...props}></Icon>
