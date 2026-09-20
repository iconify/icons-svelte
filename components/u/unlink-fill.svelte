<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugu7h1-mz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ugu7h1-mz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:unlink-fill" {...props}></Icon>
