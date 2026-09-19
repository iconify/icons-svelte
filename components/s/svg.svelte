<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejnf3c28v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ejnf3c28v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:svg" {...props}></Icon>
