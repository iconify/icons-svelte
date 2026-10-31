<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfpzj2bdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kfpzj2bdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:tent-gloss" {...props}></Icon>
