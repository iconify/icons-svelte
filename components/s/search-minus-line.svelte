<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkuguacuk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kkuguacuk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:search-minus-line" {...props}></Icon>
