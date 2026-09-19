<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejftj-b1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ejftj-b1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:tophat" {...props}></Icon>
