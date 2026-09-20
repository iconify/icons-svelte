<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwd09ej6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kwd09ej6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:text-file-remix" {...props}></Icon>
