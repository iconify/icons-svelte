<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gj97-rzku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="gj97-rzku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:thermometer-4" {...props}></Icon>
