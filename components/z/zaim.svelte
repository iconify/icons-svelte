<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oskty9h7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oskty9h7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:zaim" {...props}></Icon>
