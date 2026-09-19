<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/teylzlcrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="teylzlcrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:user-remove" {...props}></Icon>
