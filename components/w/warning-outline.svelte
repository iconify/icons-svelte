<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e75g48bdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="e75g48bdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:warning-outline" {...props}></Icon>
