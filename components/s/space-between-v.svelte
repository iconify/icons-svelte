<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7ae3acat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b7ae3acat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:space-between-v" {...props}></Icon>
