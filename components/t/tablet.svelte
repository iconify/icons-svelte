<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujnlsrl9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":18,"height":24};
const content = `<path class="ujnlsrl9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:tablet" {...props}></Icon>
