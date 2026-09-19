<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0gy0ob6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="s0gy0ob6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:w-outline" {...props}></Icon>
