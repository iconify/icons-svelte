<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtun522li.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vtun522li"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:text-align-right" {...props}></Icon>
