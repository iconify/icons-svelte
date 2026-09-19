<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fuua-_mlx.css';
import '../../css/w/w2u3wgntp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fuua-_mlx"/><path class="w2u3wgntp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:trash-can" {...props}></Icon>
