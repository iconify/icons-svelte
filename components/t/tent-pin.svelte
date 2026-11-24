<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajltlvp6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ajltlvp6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:tent-pin" {...props}></Icon>
