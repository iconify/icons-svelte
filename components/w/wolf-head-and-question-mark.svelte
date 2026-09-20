<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlxc--bra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hlxc--bra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:wolf-head-and-question-mark" {...props}></Icon>
