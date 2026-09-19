<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlm9gfljz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jlm9gfljz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:tumblr-with-circle" {...props}></Icon>
