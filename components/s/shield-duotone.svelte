<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4p5vacnv.css';
import '../../css/g/g6usvrbga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j4p5vacnv"/><path class="g6usvrbga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:shield-duotone" {...props}></Icon>
