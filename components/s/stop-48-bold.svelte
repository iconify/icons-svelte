<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oq6s4g74y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="oq6s4g74y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:stop-48-bold" {...props}></Icon>
