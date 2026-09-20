<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5muktbfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="b5muktbfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:spa" {...props}></Icon>
