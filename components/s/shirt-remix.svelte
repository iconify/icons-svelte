<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9c-hf5ie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="a9c-hf5ie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:shirt-remix" {...props}></Icon>
