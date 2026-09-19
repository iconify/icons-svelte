<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o46217s1u.css';
import '../../css/r/rzmpwjbst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="o46217s1u"/><path class="rzmpwjbst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:speaker-wave-16-solid" {...props}></Icon>
