<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_7wlkbup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e_7wlkbup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:shield-alt" {...props}></Icon>
