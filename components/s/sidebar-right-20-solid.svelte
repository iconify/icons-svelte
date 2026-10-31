<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cu76w6b-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="cu76w6b-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:sidebar-right-20-solid" {...props}></Icon>
