<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cb7cp6hix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cb7cp6hix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:village" {...props}></Icon>
