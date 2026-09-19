<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/je0q_k_2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="je0q_k_2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:video" {...props}></Icon>
