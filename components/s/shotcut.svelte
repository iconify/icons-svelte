<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kroacjbzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kroacjbzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:shotcut" {...props}></Icon>
