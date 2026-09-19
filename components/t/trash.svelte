<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9yj-ut0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="b9yj-ut0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:trash" {...props}></Icon>
