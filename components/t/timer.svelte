<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrtn-oi6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rrtn-oi6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:timer" {...props}></Icon>
