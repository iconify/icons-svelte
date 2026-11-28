<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nn2gh8b7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nn2gh8b7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:route" {...props}></Icon>
