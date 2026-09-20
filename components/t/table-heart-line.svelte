<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7jncbsyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d7jncbsyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:table-heart-line" {...props}></Icon>
