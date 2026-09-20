<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ry9s8ub7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ry9s8ub7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:user-alt-3-line" {...props}></Icon>
