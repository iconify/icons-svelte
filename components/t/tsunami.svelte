<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/es6v1qf0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="es6v1qf0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:tsunami" {...props}></Icon>
