<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zaygjqbjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":17};
const content = `<path class="zaygjqbjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:sign-road-2" {...props}></Icon>
