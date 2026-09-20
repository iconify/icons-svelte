<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwzh7abjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jwzh7abjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:square-scissors" {...props}></Icon>
