<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncq58objw.css';
import '../../css/a/a9-2q4bgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ncq58objw"/><path class="a9-2q4bgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:seaweed-20" {...props}></Icon>
