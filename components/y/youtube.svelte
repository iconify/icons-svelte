<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyi7gccyf.css';
import '../../css/u/u86mi1b2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hyi7gccyf"/><path class="u86mi1b2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:youtube" {...props}></Icon>
