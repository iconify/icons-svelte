<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6s21bb2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u6s21bb2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:warehouse-gloss" {...props}></Icon>
