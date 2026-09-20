<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnsu8pbcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pnsu8pbcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:umbrella" {...props}></Icon>
