<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2z9bdfzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n2z9bdfzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:social-tumblr-outline" {...props}></Icon>
