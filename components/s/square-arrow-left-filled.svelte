<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jc3v66bla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jc3v66bla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:square-arrow-left-filled" {...props}></Icon>
