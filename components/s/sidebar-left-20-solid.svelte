<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6d0c85zb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="o6d0c85zb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:sidebar-left-20-solid" {...props}></Icon>
