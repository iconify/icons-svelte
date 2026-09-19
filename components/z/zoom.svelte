<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sn8jj4b7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sn8jj4b7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:zoom" {...props}></Icon>
