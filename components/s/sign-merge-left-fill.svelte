<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqoepybei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nqoepybei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:sign-merge-left-fill" {...props}></Icon>
