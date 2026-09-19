<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0g9j6bqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="v0g9j6bqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:ui-preferences" {...props}></Icon>
