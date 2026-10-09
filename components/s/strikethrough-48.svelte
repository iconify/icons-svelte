<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqtu_acra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sqtu_acra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:strikethrough-48" {...props}></Icon>
