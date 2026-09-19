<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-lzg5sjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="o-lzg5sjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:text" {...props}></Icon>
