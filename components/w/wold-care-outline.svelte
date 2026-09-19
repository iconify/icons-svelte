<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ic208x0qi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ic208x0qi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:wold-care-outline" {...props}></Icon>
