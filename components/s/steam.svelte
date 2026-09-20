<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zuvs13buz.css';
import '../../css/i/imty9-5fx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zuvs13buz"/><path class="imty9-5fx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:steam" {...props}></Icon>
