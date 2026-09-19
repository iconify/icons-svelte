<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/km9q51bpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="km9q51bpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:xing" {...props}></Icon>
