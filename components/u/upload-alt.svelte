<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ybqkib0xe.css';
import '../../css/t/t9chy47bb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ybqkib0xe"/><path class="t9chy47bb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:upload-alt" {...props}></Icon>
