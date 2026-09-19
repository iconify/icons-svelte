<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnv2_3btd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":717,"height":707};
const content = `<path class="bnv2_3btd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:web" {...props}></Icon>
