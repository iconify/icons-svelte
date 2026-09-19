<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pe2q5pf1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pe2q5pf1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:sign-post" {...props}></Icon>
