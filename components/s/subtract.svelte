<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-2mshbqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f-2mshbqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:subtract" {...props}></Icon>
