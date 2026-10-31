<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fd6bibcxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fd6bibcxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:shield-x-gloss" {...props}></Icon>
