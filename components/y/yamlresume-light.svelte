<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ez0hwtbxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ez0hwtbxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:yamlresume-light" {...props}></Icon>
