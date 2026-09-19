<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-yyopb-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="g-yyopb-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:sign-intersection-y-fill" {...props}></Icon>
