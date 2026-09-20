<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/haz8azb9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="haz8azb9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:spedometer-middle-outline" {...props}></Icon>
