<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkc7pb9ss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tkc7pb9ss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:steinberg" {...props}></Icon>
