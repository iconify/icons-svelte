<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rn_s63-uz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rn_s63-uz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ruby-on-rails" {...props}></Icon>
