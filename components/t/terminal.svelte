<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4770sjkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="h4770sjkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:terminal" {...props}></Icon>
