<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igkq-7b-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="igkq-7b-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:wind-arrow-up" {...props}></Icon>
