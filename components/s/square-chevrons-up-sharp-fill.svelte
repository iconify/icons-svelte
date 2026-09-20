<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7s6gibfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s7s6gibfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-chevrons-up-sharp-fill" {...props}></Icon>
