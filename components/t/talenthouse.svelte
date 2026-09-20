<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eg5qv8bed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eg5qv8bed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:talenthouse" {...props}></Icon>
