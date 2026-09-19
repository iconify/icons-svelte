<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdii5ibko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fdii5ibko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:star" {...props}></Icon>
