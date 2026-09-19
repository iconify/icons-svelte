<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eb1db1bfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="eb1db1bfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:virus-research-alt" {...props}></Icon>
