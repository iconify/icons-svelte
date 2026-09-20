<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0c0dybby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j0c0dybby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:temperature-fahrenheit" {...props}></Icon>
