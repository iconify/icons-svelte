<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r680gbctx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r680gbctx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:sanitizer-alt" {...props}></Icon>
