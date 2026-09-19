<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8lr8p0he.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="u8lr8p0he"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:smaller-small" {...props}></Icon>
