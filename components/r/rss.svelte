<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7n3pkxoe.css';
import '../../css/y/yy8wd3b-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l7n3pkxoe"/><path class="yy8wd3b-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:rss" {...props}></Icon>
