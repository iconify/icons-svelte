<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dyali4btz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dyali4btz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:table-large-remove" {...props}></Icon>
