<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3sktvbkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="b3sktvbkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:youko-with-circle" {...props}></Icon>
