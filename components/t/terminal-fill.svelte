<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qn5sxthph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qn5sxthph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:terminal-fill" {...props}></Icon>
