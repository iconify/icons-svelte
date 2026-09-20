<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dp8ypacyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dp8ypacyq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:svg" {...props}></Icon>
