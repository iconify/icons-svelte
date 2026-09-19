<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fytct9b5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="fytct9b5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:village-outline" {...props}></Icon>
