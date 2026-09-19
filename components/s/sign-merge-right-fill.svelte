<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vg8v_ccue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vg8v_ccue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:sign-merge-right-fill" {...props}></Icon>
