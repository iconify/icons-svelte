<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdh90fr2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tdh90fr2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sparkles-48-bold" {...props}></Icon>
