<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ea13a9b2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ea13a9b2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:sign-intersection-t-fill" {...props}></Icon>
