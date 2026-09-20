<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/em_k27bbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="em_k27bbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:whole-word-sharp-fill" {...props}></Icon>
