<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpt8t_sgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kpt8t_sgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rudder-line" {...props}></Icon>
