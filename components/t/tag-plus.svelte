<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lapgvwb9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lapgvwb9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:tag-plus" {...props}></Icon>
