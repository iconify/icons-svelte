<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to0ql8b0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="to0ql8b0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:swisscows" {...props}></Icon>
