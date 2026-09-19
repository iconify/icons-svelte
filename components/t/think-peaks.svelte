<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h51gskqbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="h51gskqbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:think-peaks" {...props}></Icon>
