<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gv254yk6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gv254yk6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:triangle-inverted-large" {...props}></Icon>
