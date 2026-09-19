<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kee_ltbgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="kee_ltbgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:up-circle" {...props}></Icon>
