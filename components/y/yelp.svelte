<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/am18m6ban.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1026};
const content = `<path class="am18m6ban"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:yelp" {...props}></Icon>
