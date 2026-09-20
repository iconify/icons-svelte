<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ht5kbo4uh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ht5kbo4uh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:screwdriver-solid" {...props}></Icon>
