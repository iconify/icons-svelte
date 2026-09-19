<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ll-p0ub7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ll-p0ub7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:user-pin" {...props}></Icon>
