<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/e/e91jz5-tm.css';
import '../../css/s/sx0ycobsk.css';
import '../../css/c/cd2zdpbnx.css';
import '../../css/b/bzudmbcps.css';
import '../../css/i/if4zqtb9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="e91jz5-tm"/><path class="sx0ycobsk"/><path class="cd2zdpbnx"/><path class="bzudmbcps"/><path class="if4zqtb9v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:speaker" {...props}></Icon>
