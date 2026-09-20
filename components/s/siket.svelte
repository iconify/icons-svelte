<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdf8mjbji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":214,"height":308};
const content = `<path class="sdf8mjbji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:siket" {...props}></Icon>
