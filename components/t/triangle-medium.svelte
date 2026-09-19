<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdfm59b0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jdfm59b0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:triangle-medium" {...props}></Icon>
