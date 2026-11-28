<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsmaewb7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="jsmaewb7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:text-wrap-slash-fill" {...props}></Icon>
