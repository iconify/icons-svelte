<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ng5xczucu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ng5xczucu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:text-underline" {...props}></Icon>
