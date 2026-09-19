<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zl0na6brv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zl0na6brv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:shape-polygon" {...props}></Icon>
