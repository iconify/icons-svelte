<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvuu3lwoi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hvuu3lwoi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:sessionize" {...props}></Icon>
