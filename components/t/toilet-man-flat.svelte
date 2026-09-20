<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlptpho3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jlptpho3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:toilet-man-flat" {...props}></Icon>
