<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uc5zuv2sx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="uc5zuv2sx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:table-top-header" {...props}></Icon>
