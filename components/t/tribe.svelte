<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w27hj6qej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w27hj6qej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:tribe" {...props}></Icon>
