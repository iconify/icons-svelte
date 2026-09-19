<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkt4d55tb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="dkt4d55tb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:triangle-inverted-small2x-outline" {...props}></Icon>
