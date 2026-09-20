<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dl55wk13u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dl55wk13u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:slideshare" {...props}></Icon>
