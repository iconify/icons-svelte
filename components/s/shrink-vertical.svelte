<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zsse2tbmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zsse2tbmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:shrink-vertical" {...props}></Icon>
