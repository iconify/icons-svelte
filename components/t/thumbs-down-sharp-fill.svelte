<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yl6u6_7vh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yl6u6_7vh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:thumbs-down-sharp-fill" {...props}></Icon>
