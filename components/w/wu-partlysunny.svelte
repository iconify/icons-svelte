<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xa26vbb5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="xa26vbb5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:wu-partlysunny" {...props}></Icon>
