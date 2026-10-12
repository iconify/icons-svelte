<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9g2lac9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c9g2lac9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:thumbs-up-fill-20" {...props}></Icon>
