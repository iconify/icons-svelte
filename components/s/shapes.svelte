<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmbv0z7pc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jmbv0z7pc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:shapes" {...props}></Icon>
