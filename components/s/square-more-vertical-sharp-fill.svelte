<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2q3aujem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i2q3aujem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-more-vertical-sharp-fill" {...props}></Icon>
