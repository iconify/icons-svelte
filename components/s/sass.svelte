<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndg28nbae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ndg28nbae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:sass" {...props}></Icon>
