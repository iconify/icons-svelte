<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cz9mvhbjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cz9mvhbjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:shrink-bold" {...props}></Icon>
