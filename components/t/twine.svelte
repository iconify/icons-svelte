<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yr945gcia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="yr945gcia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:twine" {...props}></Icon>
