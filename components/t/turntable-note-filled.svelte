<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fsvgi0bxr.css';
import '../../css/e/eojx8bb3q.css';
import '../../css/z/zxkqjubrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="fsvgi0bxr"/><path class="eojx8bb3q"/><path clip-rule="evenodd" class="zxkqjubrb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:turntable-note-filled" {...props}></Icon>
