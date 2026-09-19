<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/euq48-b2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="euq48-b2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:virus-shield" {...props}></Icon>
