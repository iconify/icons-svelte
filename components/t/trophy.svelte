<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8eya-ubx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a8eya-ubx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:trophy" {...props}></Icon>
