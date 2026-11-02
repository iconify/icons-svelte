<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pf66ygd6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pf66ygd6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:user-remove-line" {...props}></Icon>
