<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5l64hbja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k5l64hbja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:suitcase-2" {...props}></Icon>
