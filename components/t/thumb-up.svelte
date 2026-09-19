<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s672d3bog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="s672d3bog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:thumb-up" {...props}></Icon>
