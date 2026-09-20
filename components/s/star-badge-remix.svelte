<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/or1zg4btw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="or1zg4btw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:star-badge-remix" {...props}></Icon>
