<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zyu8e9b8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zyu8e9b8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:storm-48" {...props}></Icon>
