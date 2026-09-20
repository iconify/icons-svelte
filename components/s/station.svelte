<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnr7b16vr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="vnr7b16vr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:station" {...props}></Icon>
