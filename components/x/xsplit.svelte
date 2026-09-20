<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tt0guk9-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tt0guk9-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:xsplit" {...props}></Icon>
