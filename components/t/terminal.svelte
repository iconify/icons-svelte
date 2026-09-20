<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jphtyabjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-4,"top":-5};
const content = `<path class="jphtyabjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:terminal" {...props}></Icon>
