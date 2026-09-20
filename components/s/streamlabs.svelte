<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5y_5b-4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a5y_5b-4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:streamlabs" {...props}></Icon>
