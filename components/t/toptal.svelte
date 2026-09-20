<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f09eohm9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f09eohm9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:toptal" {...props}></Icon>
