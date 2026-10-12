<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnlhf185u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bnlhf185u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:translation-20" {...props}></Icon>
