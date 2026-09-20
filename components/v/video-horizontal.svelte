<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uuq22r3pw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uuq22r3pw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:video-horizontal" {...props}></Icon>
