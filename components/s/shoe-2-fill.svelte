<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7tbu7-pl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e7tbu7-pl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:shoe-2-fill" {...props}></Icon>
