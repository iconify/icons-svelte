<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b90q36xnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="b90q36xnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:triangle-right" {...props}></Icon>
