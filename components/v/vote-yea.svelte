<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vclarl8ed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="vclarl8ed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:vote-yea" {...props}></Icon>
