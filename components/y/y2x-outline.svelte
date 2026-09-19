<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvi3ftn6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="hvi3ftn6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:y2x-outline" {...props}></Icon>
