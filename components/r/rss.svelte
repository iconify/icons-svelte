<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymq0d1b4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ymq0d1b4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:rss" {...props}></Icon>
