<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gb3c-dh8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gb3c-dh8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:volume-low-solid" {...props}></Icon>
