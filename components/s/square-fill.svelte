<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8x9nroua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="o8x9nroua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:square-fill" {...props}></Icon>
