<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-nyvlbsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="g-nyvlbsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:synagogue" {...props}></Icon>
