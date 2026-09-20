<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5thofbec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="l5thofbec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:speaker-1-remix" {...props}></Icon>
