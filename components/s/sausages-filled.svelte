<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-ingig5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f-ingig5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:sausages-filled" {...props}></Icon>
