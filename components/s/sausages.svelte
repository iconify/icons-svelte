<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7c7infol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q7c7infol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:sausages" {...props}></Icon>
