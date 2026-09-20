<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epw0eyb6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="epw0eyb6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:terser" {...props}></Icon>
