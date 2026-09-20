<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edbh0-1ls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="edbh0-1ls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:tablet-fill" {...props}></Icon>
