<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ho4am6oor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ho4am6oor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:straico" {...props}></Icon>
