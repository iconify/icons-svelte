<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co-40o1eu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="co-40o1eu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:virus-alt-outline" {...props}></Icon>
