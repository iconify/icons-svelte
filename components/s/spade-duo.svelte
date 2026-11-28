<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/znq7qdb9f.css';
import '../../css/a/ak0d4abdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary znq7qdb9f"/><path class="ak0d4abdn primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:spade-duo" {...props}></Icon>
