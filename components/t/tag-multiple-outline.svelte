<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4glqa34t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f4glqa34t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tag-multiple-outline" {...props}></Icon>
