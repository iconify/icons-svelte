<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aoqu9nb0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="aoqu9nb0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:shopping-bag-with-question-mark" {...props}></Icon>
