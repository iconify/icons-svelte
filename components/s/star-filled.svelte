<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkb5fmb3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gkb5fmb3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:star-filled" {...props}></Icon>
