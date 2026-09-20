<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/efh2cwtrz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="efh2cwtrz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:u-disk-fill" {...props}></Icon>
