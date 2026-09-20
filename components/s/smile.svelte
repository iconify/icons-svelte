<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbaleu4xu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fbaleu4xu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:smile" {...props}></Icon>
