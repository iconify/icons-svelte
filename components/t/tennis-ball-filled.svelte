<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvi2gab-r.css';
import '../../css/t/tctjssbck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dvi2gab-r"/><path class="tctjssbck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:tennis-ball-filled" {...props}></Icon>
