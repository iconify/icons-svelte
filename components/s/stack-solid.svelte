<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ex0eq3b5x.css';
import '../../css/d/dogo5nsjx.css';
import '../../css/z/zmc-ojbbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ex0eq3b5x"/><path class="dogo5nsjx"/><path class="zmc-ojbbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:stack-solid" {...props}></Icon>
