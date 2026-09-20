<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkf605bzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kkf605bzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:tobi" {...props}></Icon>
