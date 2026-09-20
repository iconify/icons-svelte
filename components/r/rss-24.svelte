<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xe2ertcwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xe2ertcwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:rss-24" {...props}></Icon>
