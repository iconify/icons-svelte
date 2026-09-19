<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxum_g7ec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="hxum_g7ec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:zoom-in-small-filled" {...props}></Icon>
