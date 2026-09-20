<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ul4-oqb2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ul4-oqb2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:suitcase-2-line" {...props}></Icon>
