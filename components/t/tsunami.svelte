<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbhel3d9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sbhel3d9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:tsunami" {...props}></Icon>
