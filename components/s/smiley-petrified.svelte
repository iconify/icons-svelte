<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6fnyrbeo.css';
import '../../css/p/pd0f2kbvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f6fnyrbeo"/><path class="pd0f2kbvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:smiley-petrified" {...props}></Icon>
