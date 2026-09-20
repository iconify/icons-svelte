<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsm3ucbnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jsm3ucbnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:toilet-hand-dryer" {...props}></Icon>
