<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztmtb6bgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ztmtb6bgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:sage" {...props}></Icon>
