<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jo91-lb8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jo91-lb8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:scp-foundation" {...props}></Icon>
