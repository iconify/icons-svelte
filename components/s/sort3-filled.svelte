<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zyweekm0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zyweekm0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:sort3-filled" {...props}></Icon>
