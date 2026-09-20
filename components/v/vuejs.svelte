<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/he-8tqz-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="he-8tqz-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:vuejs" {...props}></Icon>
