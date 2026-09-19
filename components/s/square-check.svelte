<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6i9ncbjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="i6i9ncbjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:square-check" {...props}></Icon>
