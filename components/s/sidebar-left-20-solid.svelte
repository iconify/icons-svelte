<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/an7mdmbof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="an7mdmbof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:sidebar-left-20-solid" {...props}></Icon>
