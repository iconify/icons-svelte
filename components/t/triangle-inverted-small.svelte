<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/su52d4bzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="su52d4bzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:triangle-inverted-small" {...props}></Icon>
