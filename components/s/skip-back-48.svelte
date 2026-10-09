<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7w6f-o8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="o7w6f-o8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:skip-back-48" {...props}></Icon>
