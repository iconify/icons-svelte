<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbr-skw7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jbr-skw7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:table" {...props}></Icon>
