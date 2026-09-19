<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqz6lxyaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kqz6lxyaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:shape-intersect" {...props}></Icon>
