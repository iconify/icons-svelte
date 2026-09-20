<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hier0ac3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hier0ac3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:warnerbros" {...props}></Icon>
