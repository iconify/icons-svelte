<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqjpjy1gs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="mqjpjy1gs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:surgical-sterilization-outline" {...props}></Icon>
