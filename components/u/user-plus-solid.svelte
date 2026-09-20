<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4al6hb4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="p4al6hb4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:user-plus-solid" {...props}></Icon>
