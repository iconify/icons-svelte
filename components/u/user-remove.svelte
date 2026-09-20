<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xs1z3_bnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xs1z3_bnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:user-remove" {...props}></Icon>
