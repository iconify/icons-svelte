<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9-cefbta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="o9-cefbta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:sign-in-16" {...props}></Icon>
