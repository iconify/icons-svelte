<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7hwuabpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="a7hwuabpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:shield-16-solid" {...props}></Icon>
