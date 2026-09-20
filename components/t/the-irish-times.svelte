<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fptaiupgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fptaiupgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:the-irish-times" {...props}></Icon>
