<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c13zd-d2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c13zd-d2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:tumulus" {...props}></Icon>
