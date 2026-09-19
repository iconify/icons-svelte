<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncykuk6wt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ncykuk6wt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:speaker-wave" {...props}></Icon>
