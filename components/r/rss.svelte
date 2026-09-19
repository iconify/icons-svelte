<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-_27iyyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l-_27iyyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:rss" {...props}></Icon>
