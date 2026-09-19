<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3_h01beb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="r3_h01beb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:y" {...props}></Icon>
