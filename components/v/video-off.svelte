<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ho98fkb4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ho98fkb4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:video-off" {...props}></Icon>
