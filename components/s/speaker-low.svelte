<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owxqd0bmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="owxqd0bmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:speaker-low" {...props}></Icon>
