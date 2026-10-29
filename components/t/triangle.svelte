<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/leji0sgjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="leji0sgjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:triangle" {...props}></Icon>
