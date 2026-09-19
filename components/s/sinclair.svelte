<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6b-56b1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g6b-56b1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:sinclair" {...props}></Icon>
