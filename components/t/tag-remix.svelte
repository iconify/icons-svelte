<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vakb-pqpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vakb-pqpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:tag-remix" {...props}></Icon>
