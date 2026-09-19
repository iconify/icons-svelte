<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0q_w7t3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b0q_w7t3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:social-github" {...props}></Icon>
