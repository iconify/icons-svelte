<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7gtsxy4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h7gtsxy4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:trend-arrow-up-light" {...props}></Icon>
