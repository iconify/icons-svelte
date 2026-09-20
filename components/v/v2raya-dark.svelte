<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bk4w45bgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bk4w45bgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:v2raya-dark" {...props}></Icon>
