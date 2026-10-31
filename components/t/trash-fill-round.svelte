<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8hmt80gq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o8hmt80gq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:trash-fill-round" {...props}></Icon>
