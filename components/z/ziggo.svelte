<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ui42cb9px.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ui42cb9px"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:ziggo" {...props}></Icon>
