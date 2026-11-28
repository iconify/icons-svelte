<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2wx7xb5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="h2wx7xb5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:sidebar-simple-open-bold" {...props}></Icon>
